<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n279pebde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n279pebde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:topology-star-2" {...props}></Icon>
