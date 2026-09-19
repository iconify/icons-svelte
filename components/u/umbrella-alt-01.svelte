<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3uf27rlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3uf27rlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:umbrella-alt-01" {...props}></Icon>
