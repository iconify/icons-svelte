<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaqdor5_y.css';
import '../../css/i/i9270-aoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iaqdor5_y"/><path class="i9270-aoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:temperature-duotone" {...props}></Icon>
