<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6-bybb5v.css';
import '../../css/j/jfhqsv3mp.css';
import '../../css/q/qddp9ybsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s6-bybb5v"/><path class="jfhqsv3mp"/><path class="qddp9ybsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:swimming-bold" {...props}></Icon>
