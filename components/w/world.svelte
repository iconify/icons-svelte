<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/naq8hacyq.css';
import '../../css/y/yj8iwvbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="naq8hacyq"/><path class="yj8iwvbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:world" {...props}></Icon>
