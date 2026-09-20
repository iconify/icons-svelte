<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj_82edkf.css';
import '../../css/b/b6u88sbza.css';
import '../../css/v/vy16ljbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj_82edkf"/><path class="b6u88sbza"/><path class="vy16ljbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:translate-solid" {...props}></Icon>
