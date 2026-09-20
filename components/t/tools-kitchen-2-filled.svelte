<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dolkt7wiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dolkt7wiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tools-kitchen-2-filled" {...props}></Icon>
