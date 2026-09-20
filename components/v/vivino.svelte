<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-0onelyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-0onelyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vivino" {...props}></Icon>
