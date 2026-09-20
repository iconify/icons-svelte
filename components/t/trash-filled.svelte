<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua1qlsq4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua1qlsq4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:trash-filled" {...props}></Icon>
