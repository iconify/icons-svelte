<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwudjlbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1001,"height":1000};
const content = `<path class="qwudjlbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:spin4" {...props}></Icon>
