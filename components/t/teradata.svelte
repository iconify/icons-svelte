<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd7ayf6fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd7ayf6fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:teradata" {...props}></Icon>
