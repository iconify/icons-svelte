<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfxgjk6jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfxgjk6jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:safety-float-bold" {...props}></Icon>
