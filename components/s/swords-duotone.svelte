<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n05sznbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n05sznbcj primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:swords-duotone" {...props}></Icon>
