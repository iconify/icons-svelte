<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cozesrb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cozesrb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:seat-child" {...props}></Icon>
