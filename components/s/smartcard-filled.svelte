<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5nansb4m.css';
import '../../css/g/ghanqywqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q5nansb4m"/><rect class="ghanqywqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:smartcard-filled" {...props}></Icon>
