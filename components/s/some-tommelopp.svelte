<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1yy3pmfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o1yy3pmfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:some-tommelopp" {...props}></Icon>
