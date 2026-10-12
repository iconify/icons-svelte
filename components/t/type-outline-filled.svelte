<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwrs5jbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwrs5jbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:type-outline-filled" {...props}></Icon>
