<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc77zwbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nc77zwbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:tape-cassette-record-solid" {...props}></Icon>
