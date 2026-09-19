<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv1ykgv5n.css';
import '../../css/x/x6w6rpbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jv1ykgv5n"/><path clip-rule="evenodd" class="x6w6rpbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:test-tube-outline" {...props}></Icon>
