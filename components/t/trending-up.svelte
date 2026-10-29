<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/binil8b-i.css';
import '../../css/q/qv-bz92zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="binil8b-i"/><path class="qv-bz92zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:trending-up" {...props}></Icon>
