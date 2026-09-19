<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olsr4lj8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olsr4lj8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:steps-option" {...props}></Icon>
