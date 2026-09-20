<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poxcth_om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poxcth_om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:thumbtack" {...props}></Icon>
