<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh2k2lb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh2k2lb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:trello-solid" {...props}></Icon>
