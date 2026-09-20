<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpttwux-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpttwux-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:umbrella-filled" {...props}></Icon>
