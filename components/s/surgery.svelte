<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocwzk9s4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocwzk9s4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:surgery" {...props}></Icon>
