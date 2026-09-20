<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh3id2b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oh3id2b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:x-circle-filled" {...props}></Icon>
