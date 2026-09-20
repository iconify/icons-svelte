<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc7bo-bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc7bo-bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:toolbox-sharp" {...props}></Icon>
