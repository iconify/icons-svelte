<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clr0thirl.css';
import '../../css/c/ci_39onbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clr0thirl"/><path class="ci_39onbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:wechat" {...props}></Icon>
