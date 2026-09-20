<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovh4bhbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovh4bhbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sitecore" {...props}></Icon>
