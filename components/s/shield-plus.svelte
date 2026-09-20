<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy7l49bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy7l49bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield-plus" {...props}></Icon>
