<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jllui1bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jllui1bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:umbrella-alt-02" {...props}></Icon>
