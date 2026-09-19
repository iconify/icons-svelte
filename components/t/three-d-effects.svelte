<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhpgzke8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhpgzke8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:three-d-effects" {...props}></Icon>
