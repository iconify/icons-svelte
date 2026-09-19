<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0q9_dbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0q9_dbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:table-add" {...props}></Icon>
