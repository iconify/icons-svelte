<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5b9_rbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x5b9_rbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:salami-filled" {...props}></Icon>
