<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogv1gbb3q.css';
import '../../css/x/xp-jb6vzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogv1gbb3q"/><path class="xp-jb6vzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:science" {...props}></Icon>
