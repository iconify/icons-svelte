<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esxgz1wsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esxgz1wsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:store-sharp-fill" {...props}></Icon>
