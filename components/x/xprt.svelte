<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9qs0v4_t.css';
import '../../css/k/kphbbgbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p9qs0v4_t"/><path class="kphbbgbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xprt" {...props}></Icon>
