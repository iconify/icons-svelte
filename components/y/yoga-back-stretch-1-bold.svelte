<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj062-b3v.css';
import '../../css/l/lgz6trbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj062-b3v"/><path class="lgz6trbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:yoga-back-stretch-1-bold" {...props}></Icon>
