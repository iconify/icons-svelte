<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdlzfwoqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wdlzfwoqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:white-up-backhand-index" {...props}></Icon>
