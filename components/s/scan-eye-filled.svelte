<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq6vezb0v.css';
import '../../css/z/z_t71ccqt.css';
import '../../css/l/ltats8egd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq6vezb0v"/><path clip-rule="evenodd" class="z_t71ccqt"/><path class="ltats8egd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:scan-eye-filled" {...props}></Icon>
