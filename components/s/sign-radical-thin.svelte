<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq2n5dunw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq2n5dunw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-radical-thin" {...props}></Icon>
