<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td-iq2oif.css';
import '../../css/d/dq3pidbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td-iq2oif"/><path class="dq3pidbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:washer-filled" {...props}></Icon>
