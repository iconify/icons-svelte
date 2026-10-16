<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgljnwlus.css';
import '../../css/s/stlc3bbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192.46,"height":222.23};
const content = `<path class="jgljnwlus"/><path class="stlc3bbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tikv" {...props}></Icon>
