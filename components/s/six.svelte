<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs770bsej.css';
import '../../css/z/ztyr4ccyb.css';
import '../../css/q/q8nk54bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs770bsej"/><path class="ztyr4ccyb"/><path class="q8nk54bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:six" {...props}></Icon>
