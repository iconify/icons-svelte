<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gir9mfh4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gir9mfh4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:table-down" {...props}></Icon>
