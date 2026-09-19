<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugl89-lzx.css';
import '../../css/a/ardjzjb-d.css';
import '../../css/p/palc4vbjx.css';
import '../../css/k/krw19nbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugl89-lzx"/><path class="ardjzjb-d"/><path class="palc4vbjx"/><path class="krw19nbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:technics" {...props}></Icon>
