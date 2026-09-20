<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr2arq_kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tr2arq_kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:trash2" {...props}></Icon>
