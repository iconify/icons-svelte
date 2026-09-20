<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v08yu0bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v08yu0bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wells-fargo" {...props}></Icon>
