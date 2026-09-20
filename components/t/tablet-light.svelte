<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0hp6jb5d.css';
import '../../css/h/hzx-5b09c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0hp6jb5d"/><path class="hzx-5b09c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:tablet-light" {...props}></Icon>
