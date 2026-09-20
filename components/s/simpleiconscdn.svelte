<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byvv0d4br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byvv0d4br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:simpleiconscdn" {...props}></Icon>
