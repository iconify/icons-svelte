<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgc-4qb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xgc-4qb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:umbrella" {...props}></Icon>
