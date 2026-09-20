<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f33b351rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f33b351rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:sofa-solid" {...props}></Icon>
