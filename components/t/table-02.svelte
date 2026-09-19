<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2t02b29a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2t02b29a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:table-02" {...props}></Icon>
