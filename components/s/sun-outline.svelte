<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3m690lxe.css';
import '../../css/k/k5sw8vduq.css';
import '../../css/z/z7kdjtbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3m690lxe"/><path clip-rule="evenodd" class="k5sw8vduq"/><path class="z7kdjtbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:sun-outline" {...props}></Icon>
