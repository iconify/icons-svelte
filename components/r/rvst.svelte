<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9nycrbpr.css';
import '../../css/e/e0maw8b-r.css';
import '../../css/h/hjnsd4bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9nycrbpr"/><path class="e0maw8b-r"/><path class="hjnsd4bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rvst" {...props}></Icon>
