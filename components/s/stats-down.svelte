<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwimmtb7k.css';
import '../../css/w/wtjey9bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="qwimmtb7k"/><path class="wtjey9bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:stats-down" {...props}></Icon>
