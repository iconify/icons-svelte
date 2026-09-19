<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9g9e5wbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c9g9e5wbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:wallet-alt-03-filled" {...props}></Icon>
