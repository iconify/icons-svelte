<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dct4eibpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dct4eibpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-cog" {...props}></Icon>
