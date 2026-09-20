<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjl13jgyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kjl13jgyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:volume-x" {...props}></Icon>
