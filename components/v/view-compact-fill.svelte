<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5mqmsbgz.css';
import '../../css/j/juxduqi5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5mqmsbgz"/><path clip-rule="evenodd" class="juxduqi5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:view-compact-fill" {...props}></Icon>
