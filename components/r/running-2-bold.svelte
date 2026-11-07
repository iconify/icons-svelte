<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shc5ox2kp.css';
import '../../css/j/jerfmgb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shc5ox2kp"/><path clip-rule="evenodd" class="jerfmgb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:running-2-bold" {...props}></Icon>
