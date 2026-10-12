<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3m8f8bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y3m8f8bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-asterisk-filled" {...props}></Icon>
