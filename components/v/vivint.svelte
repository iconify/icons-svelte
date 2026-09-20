<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4q0ycbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4q0ycbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vivint" {...props}></Icon>
