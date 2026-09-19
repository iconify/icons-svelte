<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf5ffrwpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bf5ffrwpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:tag-filled" {...props}></Icon>
