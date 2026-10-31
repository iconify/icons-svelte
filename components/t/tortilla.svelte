<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg2srv-uh.css';
import '../../css/c/c4v83cb5w.css';
import '../../css/b/bqjzlrb8m.css';
import '../../css/i/i6kuee79v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pg2srv-uh"/><path class="c4v83cb5w"/><path class="bqjzlrb8m"/><path class="i6kuee79v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:tortilla" {...props}></Icon>
