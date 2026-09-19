<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coxm8-_zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coxm8-_zz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:split" {...props}></Icon>
