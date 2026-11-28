<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndp62j9zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndp62j9zc primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shuffle-duotone" {...props}></Icon>
