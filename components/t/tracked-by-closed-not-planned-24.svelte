<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilw1vqb3q.css';
import '../../css/n/ndpi73byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilw1vqb3q"/><path class="ndpi73byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:tracked-by-closed-not-planned-24" {...props}></Icon>
