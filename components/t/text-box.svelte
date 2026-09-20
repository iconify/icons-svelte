<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/w/wwsjvx.css';
import '../../css/c/c5crzc.css';
import '../../css/y/y8_5_i.css';
import '../../css/s/sqhhwo.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c wwsjvx"/><path class="a0m25c c5crzc"/><path class="a0m25c y8_5_i"/><path class="a0m25c sqhhwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:text-box" {...props}></Icon>
