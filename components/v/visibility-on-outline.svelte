<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9d687bfw.css';
import '../../css/z/zrxq4hpuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x9d687bfw"/><path clip-rule="evenodd" class="zrxq4hpuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:visibility-on-outline" {...props}></Icon>
