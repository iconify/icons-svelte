<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no2d2recs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="no2d2recs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ship" {...props}></Icon>
