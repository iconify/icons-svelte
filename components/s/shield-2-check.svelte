<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlp7nj4mq.css';
import '../../css/z/z_edm0hny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlp7nj4mq"/><path clip-rule="evenodd" class="z_edm0hny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:shield-2-check" {...props}></Icon>
