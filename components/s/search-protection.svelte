<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlzyam9bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlzyam9bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:search-protection" {...props}></Icon>
