<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsm0l9bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jsm0l9bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:unmixed-filled" {...props}></Icon>
