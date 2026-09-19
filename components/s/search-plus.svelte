<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9les70ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m9les70ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:search-plus" {...props}></Icon>
