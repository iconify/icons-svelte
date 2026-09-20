<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knhbljgzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knhbljgzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:verified" {...props}></Icon>
