<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hthlj0aha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hthlj0aha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-x-fill" {...props}></Icon>
