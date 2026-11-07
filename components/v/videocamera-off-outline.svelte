<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh82fib1q.css';
import '../../css/j/jvt0l2akk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh82fib1q"/><path clip-rule="evenodd" class="jvt0l2akk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:videocamera-off-outline" {...props}></Icon>
