<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r55xrs0iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r55xrs0iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:stomach-24px" {...props}></Icon>
