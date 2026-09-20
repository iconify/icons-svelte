<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvu1scc_a.css';
import '../../css/k/kh1pia80p.css';
import '../../css/a/aun6_3zku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wvu1scc_a"/><path clip-rule="evenodd" class="kh1pia80p"/><path class="aun6_3zku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zero" {...props}></Icon>
