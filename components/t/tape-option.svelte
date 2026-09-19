<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/row95eb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="row95eb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:tape-option" {...props}></Icon>
