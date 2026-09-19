<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h00nofbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h00nofbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:stop" {...props}></Icon>
