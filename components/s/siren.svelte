<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzjur459l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzjur459l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:siren" {...props}></Icon>
