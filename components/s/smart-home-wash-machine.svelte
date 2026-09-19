<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr06_6nqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gr06_6nqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:smart-home-wash-machine" {...props}></Icon>
