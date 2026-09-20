<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwm14abzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="lwm14abzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sign-solid" {...props}></Icon>
