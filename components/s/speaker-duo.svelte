<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5w2i-jym.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/ysbubg1kd.css';
import '../../css/t/t80vk__1t.css';
import '../../css/j/jboqyrtbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5w2i-jym secondary"/><g class="dt0cm9dhy primary"><path class="ysbubg1kd"/><path class="t80vk__1t"/><path class="jboqyrtbu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:speaker-duo" {...props}></Icon>
