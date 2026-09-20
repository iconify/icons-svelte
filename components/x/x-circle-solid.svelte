<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4q-tzb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="o4q-tzb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:x-circle-solid" {...props}></Icon>
