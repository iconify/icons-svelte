<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egbow5bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="egbow5bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:twt" {...props}></Icon>
