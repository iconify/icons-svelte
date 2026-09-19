<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cigxo612f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cigxo612f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:splits" {...props}></Icon>
