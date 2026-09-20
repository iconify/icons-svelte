<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw3q-gb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw3q-gb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:toolbox" {...props}></Icon>
