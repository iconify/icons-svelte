<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ramklfbpo.css';
import '../../css/s/s2ay7ubwo.css';
import '../../css/k/k3_giy35l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ramklfbpo"/><path class="s2ay7ubwo"/><path class="k3_giy35l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:trash" {...props}></Icon>
