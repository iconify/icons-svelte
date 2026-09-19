<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqsw8ihjc.css';
import '../../css/i/iue9lzdei.css';
import '../../css/i/ipgwi6qyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="pqsw8ihjc"/><path class="iue9lzdei"/><path class="ipgwi6qyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-deviant-art" {...props}></Icon>
