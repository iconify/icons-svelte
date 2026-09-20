<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoitpkywi.css';
import '../../css/j/j4nqo-26l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoitpkywi"/><path class="j4nqo-26l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:time-progress-duotone" {...props}></Icon>
