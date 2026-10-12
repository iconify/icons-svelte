<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfd6n_b5f.css';
import '../../css/h/h7y14-blq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hfd6n_b5f"/><path class="h7y14-blq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-cycle-20" {...props}></Icon>
