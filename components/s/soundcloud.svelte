<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgkso48rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgkso48rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:soundcloud" {...props}></Icon>
