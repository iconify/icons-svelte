<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekc384f8f.css';
import '../../css/v/vgi-dbcnj.css';
import '../../css/b/b5atfim-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="ekc384f8f"/><path class="vgi-dbcnj"/><path clip-rule="evenodd" class="b5atfim-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:tip-jar-filled" {...props}></Icon>
