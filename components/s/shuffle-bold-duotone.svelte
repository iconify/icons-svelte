<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_hji6de.css';
import '../../css/s/s41nwo9jh.css';
import '../../css/k/k8ef9sbjl.css';
import '../../css/b/blczsbbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="s41nwo9jh"/><path class="k8ef9sbjl"/><path class="blczsbbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shuffle-bold-duotone" {...props}></Icon>
