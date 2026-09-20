<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bopfs6bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bopfs6bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sefaria" {...props}></Icon>
