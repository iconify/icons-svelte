<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh4byipgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hh4byipgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:skype-solid" {...props}></Icon>
