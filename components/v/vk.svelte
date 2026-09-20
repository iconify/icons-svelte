<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9-usv-fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9-usv-fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:vk" {...props}></Icon>
