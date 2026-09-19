<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcw1domtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcw1domtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:running-filled" {...props}></Icon>
