<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnh9jo49l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vnh9jo49l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:search-minus" {...props}></Icon>
