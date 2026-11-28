<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkr0jbczq.css';
import '../../css/e/e66ctgbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkr0jbczq secondary"/><path class="e66ctgbgu primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:union-duo" {...props}></Icon>
