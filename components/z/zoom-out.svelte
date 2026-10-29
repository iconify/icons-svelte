<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgnd9bw0t.css';
import '../../css/b/bh1hcdbms.css';
import '../../css/g/g2k-h2zlv.css';
import '../../css/h/h9-ebutrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgnd9bw0t wm-a"/><path class="bh1hcdbms wm-k"/><path class="g2k-h2zlv wm-a"/><path class="h9-ebutrh wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:zoom-out" {...props}></Icon>
