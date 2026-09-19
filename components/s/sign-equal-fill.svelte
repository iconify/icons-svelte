<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpm-t2bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpm-t2bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-equal-fill" {...props}></Icon>
