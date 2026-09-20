<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grs06_b9k.css';
import '../../css/z/zvpwxgbul.css';
import '../../css/a/aq8pp-buc.css';
import '../../css/b/b925a0-jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grs06_b9k"/><path class="zvpwxgbul"/><path class="aq8pp-buc"/><path class="b925a0-jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:volkswagen" {...props}></Icon>
