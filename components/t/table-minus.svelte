<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvs5w2btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvs5w2btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:table-minus" {...props}></Icon>
