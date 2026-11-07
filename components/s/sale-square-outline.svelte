<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woe0hukjy.css';
import '../../css/c/c_jaw7s9r.css';
import '../../css/s/s8ujp6b8o.css';
import '../../css/h/hjkpptbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woe0hukjy"/><path class="c_jaw7s9r"/><path clip-rule="evenodd" class="s8ujp6b8o"/><path clip-rule="evenodd" class="hjkpptbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sale-square-outline" {...props}></Icon>
