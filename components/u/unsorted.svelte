<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lghk2q9iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lghk2q9iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:unsorted" {...props}></Icon>
