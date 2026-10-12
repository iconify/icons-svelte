<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un164r4db.css';
import '../../css/m/m_0bwy7ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="un164r4db"/><path class="m_0bwy7ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:timer-filled" {...props}></Icon>
